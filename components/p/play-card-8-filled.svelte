<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wpgv93bax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wpgv93bax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:play-card-8-filled" {...props}></Icon>
