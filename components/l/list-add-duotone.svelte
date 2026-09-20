<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l8cfgjbhe.css';
import '../../css/b/b6b-u_35t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l8cfgjbhe"/><path class="b6b-u_35t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:list-add-duotone" {...props}></Icon>
