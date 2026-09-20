<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uas_n9iqv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uas_n9iqv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:crwny" {...props}></Icon>
