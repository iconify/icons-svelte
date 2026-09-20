<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o6pex7q3c.css';
import '../../css/r/rgqpz_b2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o6pex7q3c"/><path class="rgqpz_b2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:nom" {...props}></Icon>
