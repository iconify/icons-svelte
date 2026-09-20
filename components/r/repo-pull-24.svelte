<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ceknmg57b.css';
import '../../css/a/agohndbfp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ceknmg57b"/><path class="agohndbfp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:repo-pull-24" {...props}></Icon>
