<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pfi146w-l.css';
import '../../css/e/eeps4wpgj.css';
import '../../css/s/sfb8rqn9v.css';
import '../../css/k/ksydp3lsw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pfi146w-l"/><path class="eeps4wpgj"/><path class="sfb8rqn9v"/><path class="ksydp3lsw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:power-station-x-48-bold" {...props}></Icon>
