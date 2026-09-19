<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/usr8d0vnk.css';
import '../../css/m/my-g78bbf.css';
import '../../css/i/ibd18pb0y.css';
import '../../css/u/uvm8k6bog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="usr8d0vnk"/><path class="my-g78bbf"/><circle class="ibd18pb0y"/><circle class="uvm8k6bog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:face-frown" {...props}></Icon>
