<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/skiv409wp.css';
import '../../css/v/v5f6axbii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="skiv409wp"/><path class="v5f6axbii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:burger-arrow-left-duotone" {...props}></Icon>
