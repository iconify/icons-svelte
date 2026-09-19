<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vqn7c3blc.css';
import '../../css/b/bfe0-acgo.css';
import '../../css/u/uaq5afiat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="vqn7c3blc"/><path class="bfe0-acgo"/><circle class="uaq5afiat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:patterns" {...props}></Icon>
