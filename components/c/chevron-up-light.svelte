<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v68lmw7lf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v68lmw7lf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:chevron-up-light" {...props}></Icon>
