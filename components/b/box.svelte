<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ffhh3qb8v.css';
import '../../css/s/sfre7fbzt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ffhh3qb8v"/><path class="sfre7fbzt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:box" {...props}></Icon>
