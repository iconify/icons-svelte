<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gs6ukqbqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gs6ukqbqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:gift" {...props}></Icon>
