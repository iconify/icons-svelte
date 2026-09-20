<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qaa98ibfx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="qaa98ibfx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:circle-on" {...props}></Icon>
