<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jjx8q2jsf.css';
import '../../css/e/ez3axdbjz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jjx8q2jsf"/><path class="ez3axdbjz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:arrow-up-20-bold" {...props}></Icon>
