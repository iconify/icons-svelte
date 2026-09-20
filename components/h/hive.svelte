<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mem23212o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mem23212o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:hive" {...props}></Icon>
