<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/va6jvlbzo.css';
import '../../css/y/y0kw6z96g.css';
import '../../css/d/dgq02yorw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="va6jvlbzo"/><path class="y0kw6z96g"/><path class="dgq02yorw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:nodered" {...props}></Icon>
