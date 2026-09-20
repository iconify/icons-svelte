<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gigmts-4w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gigmts-4w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:check-alt-fill" {...props}></Icon>
