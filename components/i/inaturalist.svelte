<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a89ur2b1j.css';
import '../../css/x/x15omc94k.css';
import '../../css/a/alf0loboi.css';
import '../../css/v/vr7_nrb-q.css';
import '../../css/s/s4wohcc5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path clip-rule="evenodd" class="a89ur2b1j"/><path class="x15omc94k"/><circle class="alf0loboi"/><path class="vr7_nrb-q"/><path class="s4wohcc5l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:inaturalist" {...props}></Icon>
