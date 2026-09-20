<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v4or_ln8c.css';
import '../../css/p/pmdjauv5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v4or_ln8c"/><path class="pmdjauv5d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:image-ban-light" {...props}></Icon>
