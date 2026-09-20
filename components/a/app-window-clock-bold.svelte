<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ty1e_gbpu.css';
import '../../css/a/aljx-nbqm.css';
import '../../css/i/iluxvyfjm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ty1e_gbpu"/><path class="aljx-nbqm"/><path class="iluxvyfjm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:app-window-clock-bold" {...props}></Icon>
