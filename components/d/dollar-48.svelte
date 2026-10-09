<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cvtb9mbah.css';
import '../../css/n/ndrbb8byy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="cvtb9mbah"/><path class="ndrbb8byy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:dollar-48" {...props}></Icon>
