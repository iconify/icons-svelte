<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q2ik5l0cf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q2ik5l0cf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:heroku" {...props}></Icon>
