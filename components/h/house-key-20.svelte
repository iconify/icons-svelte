<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p7juawdew.css';
import '../../css/v/v0h2-7bys.css';
import '../../css/c/ctzl9ackg.css';
import '../../css/p/psrlxpb8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="p7juawdew"/><path class="v0h2-7bys"/><path class="ctzl9ackg"/><path class="psrlxpb8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:house-key-20" {...props}></Icon>
