<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u2v4it5to.css';
import '../../css/v/velavw33g.css';
import '../../css/k/krzgvzbvy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u2v4it5to"/><path class="velavw33g"/><path class="krzgvzbvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:private-content-light" {...props}></Icon>
