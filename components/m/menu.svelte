<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vj8qeqbpz.css';
import '../../css/i/itzm3abxz.css';
import '../../css/y/ycxg46bhx.css';
import '../../css/l/lcqxtqbuo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-primary-layer vj8qeqbpz"/><path class="duoicon-secondary-layer itzm3abxz"/><path class="duoicon-primary-layer ycxg46bhx"/><path class="duoicon-secondary-layer lcqxtqbuo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="duo-icons:menu" {...props}></Icon>
