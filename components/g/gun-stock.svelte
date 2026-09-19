<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oh3a-cbel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oh3a-cbel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:gun-stock" {...props}></Icon>
