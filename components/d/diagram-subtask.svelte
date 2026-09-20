<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g4z24m8di.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g4z24m8di"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:diagram-subtask" {...props}></Icon>
