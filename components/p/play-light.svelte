<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hgi0-jbur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hgi0-jbur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:play-light" {...props}></Icon>
