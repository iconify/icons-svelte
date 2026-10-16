<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kj4vzjb5q.css';
import '../../css/v/vnif4gbyf.css';
import '../../css/y/ye5cuebhj.css';
import '../../css/i/iclthgb7p.css';
import '../../css/n/nrwsk66dz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="kj4vzjb5q"/><path class="vnif4gbyf"/><path class="ye5cuebhj"/><path class="iclthgb7p"/><path class="nrwsk66dz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:repowering-20" {...props}></Icon>
