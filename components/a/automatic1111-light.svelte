<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/atu2sub5i.css';
import '../../css/f/fwkrdacaj.css';
import '../../css/u/ujhpcdopf.css';
import '../../css/s/sf7c3hbxk.css';
import '../../css/d/dvjvyb1np.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="atu2sub5i"/><path class="fwkrdacaj"/><path class="ujhpcdopf"/><path class="sf7c3hbxk"/><path class="dvjvyb1np"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:automatic1111-light" {...props}></Icon>
