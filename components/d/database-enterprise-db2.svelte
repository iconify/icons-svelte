<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-8vxrbgb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="v-8vxrbgb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:database-enterprise-db2" {...props}></Icon>
