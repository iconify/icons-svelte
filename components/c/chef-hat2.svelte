<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j__43mbko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j__43mbko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:chef-hat2" {...props}></Icon>
