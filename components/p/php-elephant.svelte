<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zpju4dvus.css';
import '../../css/v/v1aw9_kpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zpju4dvus"/><path class="v1aw9_kpp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:php-elephant" {...props}></Icon>
