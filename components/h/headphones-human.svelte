<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aitggjtuy.css';
import '../../css/g/g8i58htec.css';
import '../../css/i/ix-fez9nl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aitggjtuy"/><path class="g8i58htec"/><path class="ix-fez9nl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:headphones-human" {...props}></Icon>
