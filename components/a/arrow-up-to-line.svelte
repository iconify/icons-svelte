<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h4787ac0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h4787ac0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:arrow-up-to-line" {...props}></Icon>
