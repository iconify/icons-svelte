<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/szqzdbcks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="szqzdbcks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:halloween-cat" {...props}></Icon>
