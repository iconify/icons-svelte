<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/txdk-rk8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="txdk-rk8y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-databricks" {...props}></Icon>
