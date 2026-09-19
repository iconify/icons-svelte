<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/i/igc2mbcca.css';
import '../../css/l/l5goj9tdn.css';
import '../../css/a/abpbqzb9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="hntgybcog"><circle class="igc2mbcca"/><circle class="l5goj9tdn"/><circle class="abpbqzb9d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="charm:menu-kebab" {...props}></Icon>
