<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-lopnnqb.css';
import '../../css/w/win9rhm6g.css';
import '../../css/n/nrkn4rbjl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path clip-rule="evenodd" class="n-lopnnqb"/><path clip-rule="evenodd" class="win9rhm6g"/><path class="nrkn4rbjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:nixos-wordmark" {...props}></Icon>
