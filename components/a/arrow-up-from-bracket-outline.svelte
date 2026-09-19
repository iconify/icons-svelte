<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bhqdajy5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bhqdajy5l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:arrow-up-from-bracket-outline" {...props}></Icon>
