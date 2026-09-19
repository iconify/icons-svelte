<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fgyq62bby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fgyq62bby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:chart-line-data" {...props}></Icon>
