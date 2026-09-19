<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hupzjybbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hupzjybbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:dot-04-l" {...props}></Icon>
