<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f45aa6gqp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f45aa6gqp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:merge-right" {...props}></Icon>
