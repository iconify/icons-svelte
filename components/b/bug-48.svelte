<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/da3bf5bbj.css';
import '../../css/g/gtz69mu0i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="da3bf5bbj"/><path class="gtz69mu0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bug-48" {...props}></Icon>
