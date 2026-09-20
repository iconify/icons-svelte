<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uuyf9rb6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uuyf9rb6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:hand-holding-dollar-light" {...props}></Icon>
