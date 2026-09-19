<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/he7habbvj.css';
import '../../css/f/f358-er9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="he7habbvj"/><path class="f358-er9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:building-house" {...props}></Icon>
