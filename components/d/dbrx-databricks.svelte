<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o_v22q00v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o_v22q00v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:dbrx-databricks" {...props}></Icon>
