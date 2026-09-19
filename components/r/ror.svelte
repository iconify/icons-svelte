<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wjn5tlbla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="wjn5tlbla"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:ror" {...props}></Icon>
