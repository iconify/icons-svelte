<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ed9bqxbqe.css';
import '../../css/a/adr3lqbau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ed9bqxbqe"/><path class="adr3lqbau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:header-6-20" {...props}></Icon>
