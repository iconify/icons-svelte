<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/swifegtcy.css';
import '../../css/f/falyj_29j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="swifegtcy"/><path class="falyj_29j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-custom-open" {...props}></Icon>
