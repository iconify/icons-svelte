<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tlnshvmru.css';
import '../../css/p/paw_-0u1j.css';
import '../../css/u/uc8gne65u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="tlnshvmru"/><path class="paw_-0u1j"/><path class="uc8gne65u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:mysql-wordmark" {...props}></Icon>
