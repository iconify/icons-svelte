<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g8q5rybnq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g8q5rybnq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:replicate" {...props}></Icon>
