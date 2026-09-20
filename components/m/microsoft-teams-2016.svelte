<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ohtbhbbcu.css';
import '../../css/o/o598_n4he.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ohtbhbbcu"/><path class="o598_n4he"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:microsoft-teams-2016" {...props}></Icon>
