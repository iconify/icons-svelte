<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q2an1vf6x.css';
import '../../css/k/k82zah-zg.css';
import '../../css/n/nnnq0zm1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q2an1vf6x"/><path class="k82zah-zg"/><path class="nnnq0zm1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:loc" {...props}></Icon>
