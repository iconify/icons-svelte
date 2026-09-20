<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uyoyz9ojw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uyoyz9ojw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:book-bookmark" {...props}></Icon>
