<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tsmhpgwcs.css';
import '../../css/d/dmi2w96im.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="tsmhpgwcs"/><path class="dmi2w96im"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:induction-hob-48" {...props}></Icon>
