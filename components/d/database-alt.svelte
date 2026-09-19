<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/huizebc3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="huizebc3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:database-alt" {...props}></Icon>
