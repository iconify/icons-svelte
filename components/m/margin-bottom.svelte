<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nc0rw33ot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nc0rw33ot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:margin-bottom" {...props}></Icon>
