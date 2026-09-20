<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qos7fzbpw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qos7fzbpw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:air-vent" {...props}></Icon>
