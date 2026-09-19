<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bc1fd0lxe.css';
import '../../css/q/qw1f0bfkg.css';
import '../../css/o/ou1b4gbff.css';
import '../../css/b/br4dn_b2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<mask id="circleFlagsLus0"><circle class="bc1fd0lxe"/></mask><g mask="url(#circleFlagsLus0)"><path class="qw1f0bfkg"/><path class="ou1b4gbff"/><circle class="br4dn_b2l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circle-flags:lus" {...props}></Icon>
