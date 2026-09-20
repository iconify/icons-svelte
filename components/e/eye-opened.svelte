<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uws2288gp.css';
import '../../css/b/b9dmkccal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uws2288gp"/><path class="b9dmkccal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:eye-opened" {...props}></Icon>
