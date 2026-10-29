<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m9ywfyxmo.css';
import '../../css/e/ebjwpkoxt.css';
import '../../css/v/v2i4q_bal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m9ywfyxmo wm-k"/><path class="ebjwpkoxt wm-a"/><path class="v2i4q_bal wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:chef-hat" {...props}></Icon>
