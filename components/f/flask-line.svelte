<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ob4bk-btd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ob4bk-btd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:flask-line" {...props}></Icon>
