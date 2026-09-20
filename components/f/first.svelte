<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mlnah18dm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mlnah18dm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:first" {...props}></Icon>
