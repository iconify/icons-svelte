<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sqypj7bca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sqypj7bca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:gender-ambiguous-solid" {...props}></Icon>
