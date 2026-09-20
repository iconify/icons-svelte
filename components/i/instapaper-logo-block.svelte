<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lhj3n1bhe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lhj3n1bhe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:instapaper-logo-block" {...props}></Icon>
