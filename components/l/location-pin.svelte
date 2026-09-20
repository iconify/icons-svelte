<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kctlzdb3q.css';
import '../../css/h/habz1g55j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kctlzdb3q"/><path class="habz1g55j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:location-pin" {...props}></Icon>
