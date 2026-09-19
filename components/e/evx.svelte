<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/al7gqttgw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="al7gqttgw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:evx" {...props}></Icon>
