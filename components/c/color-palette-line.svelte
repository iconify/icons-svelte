<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hi4rgpbsh.css';
import '../../css/i/ih3xvpyom.css';
import '../../css/j/jxgdkxb5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="hi4rgpbsh"/><path class="ih3xvpyom"/><path class="jxgdkxb5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:color-palette-line" {...props}></Icon>
