<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wpxx19b4u.css';
import '../../css/b/bq2iq2bed.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wpxx19b4u"/><path class="bq2iq2bed"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:angular-fill" {...props}></Icon>
