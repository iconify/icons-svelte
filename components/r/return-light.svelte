<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qlr5s3veu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qlr5s3veu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:return-light" {...props}></Icon>
