<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fjmqm-lbw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fjmqm-lbw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:car-taxi-front-solid" {...props}></Icon>
