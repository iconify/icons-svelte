<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mg159x5tx.css';
import '../../css/o/o-7dnvbon.css';
import '../../css/j/jowk_gb7h.css';
import '../../css/d/dqh3ukbna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mg159x5tx"/><path class="o-7dnvbon"/><path class="jowk_gb7h"/><path class="dqh3ukbna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:arbi" {...props}></Icon>
