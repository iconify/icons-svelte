<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o66gqk1ks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o66gqk1ks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:covered-jar" {...props}></Icon>
