<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oy3jago4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oy3jago4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:basecamp-logo-2-block" {...props}></Icon>
