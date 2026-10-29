<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rl_7l0b6o.css';
import '../../css/b/bjb_koami.css';
import '../../css/f/fm4je1qry.css';
import '../../css/m/mmzel9bis.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rl_7l0b6o wm-k"/><path class="bjb_koami wm-k"/><path class="fm4je1qry wm-a"/><path class="mmzel9bis wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:repeat" {...props}></Icon>
