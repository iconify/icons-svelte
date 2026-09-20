<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l1b454btw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l1b454btw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:danger-square-bold" {...props}></Icon>
