<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l284gmbdw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l284gmbdw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:lettered-list" {...props}></Icon>
