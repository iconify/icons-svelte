<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qrrw9kgyl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qrrw9kgyl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:basket-alt" {...props}></Icon>
