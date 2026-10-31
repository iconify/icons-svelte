<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2kvgvbvc.css';
import '../../css/f/fr1fxrgrl.css';
import '../../css/h/h6pp3dbux.css';
import '../../css/b/b40oykbsb.css';
import '../../css/o/o38pash6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="d2kvgvbvc"><path class="fr1fxrgrl wm-shadow"/><path class="h6pp3dbux"/><path class="b40oykbsb"/><path class="o38pash6d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-retro:git-compare" {...props}></Icon>
