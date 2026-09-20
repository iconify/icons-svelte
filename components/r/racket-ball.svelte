<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/moqid97xw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="moqid97xw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:racket-ball" {...props}></Icon>
