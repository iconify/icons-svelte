<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hoa0fbuwz.css';
import '../../css/o/o7khdv3bk.css';
import '../../css/h/hr3wh0b3g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hoa0fbuwz"/><circle class="o7khdv3bk"/><path class="hr3wh0b3g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:circle-info" {...props}></Icon>
