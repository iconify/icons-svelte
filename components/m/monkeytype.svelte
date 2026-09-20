<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bq4zvacob.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bq4zvacob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:monkeytype" {...props}></Icon>
