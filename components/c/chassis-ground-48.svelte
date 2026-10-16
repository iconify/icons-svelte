<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yqsth4bzo.css';
import '../../css/n/ng_o9qbxw.css';
import '../../css/r/rnqgbobut.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="yqsth4bzo"/><path class="ng_o9qbxw"/><path class="rnqgbobut"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chassis-ground-48" {...props}></Icon>
