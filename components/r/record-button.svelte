<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cog56gb0n.css';
import '../../css/v/v9lk8ib_s.css';
import '../../css/h/hf1-0pb9l.css';
import '../../css/w/wtahhnbyg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<circle class="cog56gb0n"/><circle class="v9lk8ib_s"/><circle class="hf1-0pb9l"/><circle class="wtahhnbyg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:record-button" {...props}></Icon>
