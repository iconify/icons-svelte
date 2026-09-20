<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y7q23qb2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y7q23qb2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:no-entry-24" {...props}></Icon>
