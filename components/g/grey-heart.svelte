<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/id-mrubfu.css';
import '../../css/f/f-moxybke.css';
import '../../css/m/m-jkwl5tc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="id-mrubfu"/><path class="f-moxybke"/><ellipse transform="rotate(30 23.477 12.592)" class="m-jkwl5tc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:grey-heart" {...props}></Icon>
