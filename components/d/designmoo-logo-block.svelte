<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ct__eybzk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ct__eybzk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:designmoo-logo-block" {...props}></Icon>
