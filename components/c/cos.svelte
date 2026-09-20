<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cibmyoejo.css';
import '../../css/t/tj7kutb3g.css';
import '../../css/t/t0c6ekb-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cibmyoejo"/><path class="tj7kutb3g"/><path class="t0c6ekb-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:cos" {...props}></Icon>
