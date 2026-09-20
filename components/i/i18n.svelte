<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gcels9qiz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gcels9qiz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:i18n" {...props}></Icon>
