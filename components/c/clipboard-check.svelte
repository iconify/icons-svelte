<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iwx5nsbif.css';
import '../../css/h/hustz32ji.css';
import '../../css/i/ieqi3o5qf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iwx5nsbif wm-k"/><path class="hustz32ji wm-a"/><path class="ieqi3o5qf wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:clipboard-check" {...props}></Icon>
