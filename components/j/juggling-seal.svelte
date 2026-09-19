<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nso-0gb7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nso-0gb7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:juggling-seal" {...props}></Icon>
