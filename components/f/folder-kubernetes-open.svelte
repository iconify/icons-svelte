<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q90-1_bvc.css';
import '../../css/q/qqn7q5bip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="q90-1_bvc"/><path class="qqn7q5bip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-kubernetes-open" {...props}></Icon>
