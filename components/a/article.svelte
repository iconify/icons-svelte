<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hlvvtbc1o.css';
import '../../css/n/nvm0pnlsd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hlvvtbc1o"/><path class="nvm0pnlsd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:article" {...props}></Icon>
