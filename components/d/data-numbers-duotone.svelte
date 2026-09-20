<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufpgrbbbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ufpgrbbbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:data-numbers-duotone" {...props}></Icon>
