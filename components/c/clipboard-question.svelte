<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eoh9qo8fk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eoh9qo8fk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:clipboard-question" {...props}></Icon>
