<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fx09ifbfj.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/d/dmlivpbhf.css';
import '../../css/u/uit7n1zka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fx09ifbfj secondary"/><g class="dt0cm9dhy primary"><path class="dmlivpbhf"/><path class="uit7n1zka"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:meteor-duo" {...props}></Icon>
