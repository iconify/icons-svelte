<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jrkewflek.css';
import '../../css/h/hwjgqrbah.css';
import '../../css/y/y9mg2tbzu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jrkewflek"/><path class="hwjgqrbah"/><path class="y9mg2tbzu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pets-allowed-48-bold" {...props}></Icon>
