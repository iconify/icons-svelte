<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pjs0b7ben.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pjs0b7ben"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:city-alt" {...props}></Icon>
