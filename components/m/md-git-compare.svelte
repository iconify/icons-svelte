<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/givycqbte.css';
import '../../css/q/qi9ru7mur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="givycqbte"/><path class="qi9ru7mur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-git-compare" {...props}></Icon>
