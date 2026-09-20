<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_-0zmhuv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c_-0zmhuv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:minus" {...props}></Icon>
