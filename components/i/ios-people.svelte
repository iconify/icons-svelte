<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/drritjblj.css';
import '../../css/w/wk4tu6b9n.css';
import '../../css/d/dkypacb8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="drritjblj"/><path class="wk4tu6b9n"/><path class="dkypacb8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-people" {...props}></Icon>
