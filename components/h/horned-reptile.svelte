<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/we5tmsjrp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="we5tmsjrp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:horned-reptile" {...props}></Icon>
